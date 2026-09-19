<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fmlnzirud.css';
import '../../css/f/fh5p1wbcf.css';
import '../../css/w/wjl0m-b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmlnzirud"/><path class="fh5p1wbcf"/><path class="wjl0m-b2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:3d-ellipse" {...props}></Icon>
