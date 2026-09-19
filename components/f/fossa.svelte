<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c10vmihzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":438,"height":512};
const content = `<path class="c10vmihzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fossa" {...props}></Icon>
