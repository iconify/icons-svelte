<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy_h3mg2o.css';
import '../../css/t/t_zwr_bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="sy_h3mg2o"/><path transform="scale(.79012 .88889)" class="t_zwr_bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:es-ct-4x3" {...props}></Icon>
