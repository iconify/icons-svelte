<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esjgdibig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esjgdibig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pod" {...props}></Icon>
