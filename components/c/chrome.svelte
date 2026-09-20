<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/md4gg0b9v.css';
import '../../css/y/ydhobwxud.css';
import '../../css/l/lmazhrbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md4gg0b9v"/><path class="ydhobwxud"/><path class="lmazhrbcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chrome" {...props}></Icon>
