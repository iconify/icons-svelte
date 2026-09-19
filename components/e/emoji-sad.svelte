<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c02b__imu.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/f/fdpjff5dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c02b__imu"/><path class="p9-zrkb4g"/><path class="fdpjff5dn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-sad" {...props}></Icon>
