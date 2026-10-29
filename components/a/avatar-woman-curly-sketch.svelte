<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lnc4jbg4z.css';
import '../../css/o/ofwm1kdcx.css';
import '../../css/e/en291ygfx.css';
import '../../css/m/m_b26hb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lnc4jbg4z wm-k"/><path class="ofwm1kdcx wm-a"/><path class="en291ygfx wm-k"/><path class="m_b26hb0h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-curly-sketch" {...props}></Icon>
