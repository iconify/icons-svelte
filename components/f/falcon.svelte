<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmlz9acfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmlz9acfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:falcon" {...props}></Icon>
