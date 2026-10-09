<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qob3urb3w.css';
import '../../css/z/zkc3a6ybf.css';
import '../../css/u/u01duyblj.css';
import '../../css/c/c5xbzriem.css';
import '../../css/g/gpd43zbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qob3urb3w"/><path class="zkc3a6ybf"/><path class="u01duyblj"/><path class="c5xbzriem"/><path class="gpd43zbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-sink-20" {...props}></Icon>
