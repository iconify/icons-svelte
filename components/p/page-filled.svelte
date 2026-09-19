<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjo68qbsq.css';
import '../../css/u/uhso3bbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zjo68qbsq"/><path class="uhso3bbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-filled" {...props}></Icon>
