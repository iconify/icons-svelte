<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hu0864bjy.css';
import '../../css/o/o-jk2xaue.css';
import '../../css/w/wg2oucbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hu0864bjy"/><path class="o-jk2xaue wm-k"/><path class="wg2oucbbj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microwave-sketch" {...props}></Icon>
