<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5r41wfxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p5r41wfxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:graphite" {...props}></Icon>
