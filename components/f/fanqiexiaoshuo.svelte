<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_cxkkhb.css';
import '../../css/o/o6uly9l0b.css';
import '../../css/s/sn2vv6rhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hj_cxkkhb"/><path class="o6uly9l0b"/><path class="sn2vv6rhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:fanqiexiaoshuo" {...props}></Icon>
