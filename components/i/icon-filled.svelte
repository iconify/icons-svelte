<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gw28ry-jh.css';
import '../../css/x/xuhaekohu.css';
import '../../css/g/g5_7laczp.css';
import '../../css/g/gi8pdrn9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gw28ry-jh"/><path class="xuhaekohu"/><path class="g5_7laczp"/><path class="gi8pdrn9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:icon-filled" {...props}></Icon>
