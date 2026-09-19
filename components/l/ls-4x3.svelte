<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/y/yfdjvu8pd.css';
import '../../css/g/gkucm_bdu.css';
import '../../css/c/c0ltoil8c.css';
import '../../css/o/owlk22_ch.css';
import '../../css/q/qslcqt1xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="yfdjvu8pd"/><path class="gkucm_bdu"/><path class="c0ltoil8c"/><path class="owlk22_ch"/><path class="qslcqt1xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ls-4x3" {...props}></Icon>
