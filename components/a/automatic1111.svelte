<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mewn8jbsb.css';
import '../../css/l/l-3emlabv.css';
import '../../css/q/qekb1nb-r.css';
import '../../css/g/gxbioacqh.css';
import '../../css/c/cpiokdbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mewn8jbsb"/><path class="l-3emlabv"/><path class="qekb1nb-r"/><path class="gxbioacqh"/><path class="cpiokdbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:automatic1111" {...props}></Icon>
