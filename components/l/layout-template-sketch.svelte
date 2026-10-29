<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dokkydlwa.css';
import '../../css/p/pf8jp1bza.css';
import '../../css/k/kni8ltbwm.css';
import '../../css/n/nz6xrlb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dokkydlwa"/><path class="pf8jp1bza wm-a"/><path class="kni8ltbwm wm-k"/><path class="nz6xrlb9f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-template-sketch" {...props}></Icon>
