<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ircnbzb.css';
import '../../css/b/bncl5bqie.css';
import '../../css/g/gdjn7oggh.css';
import '../../css/d/dwr8i5vns.css';
import '../../css/f/fy270jxws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m_ircnbzb"/><path class="bncl5bqie"/><path class="gdjn7oggh"/><path class="dwr8i5vns"/><path class="fy270jxws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:robot-arm-20-bold" {...props}></Icon>
