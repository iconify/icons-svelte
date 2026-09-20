<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ryiccth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a1ryiccth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:domed-tower" {...props}></Icon>
