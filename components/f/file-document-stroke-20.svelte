<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noxeszbuu.css';
import '../../css/y/ypv4l3ivv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="noxeszbuu"/><path class="ypv4l3ivv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-document-stroke-20" {...props}></Icon>
