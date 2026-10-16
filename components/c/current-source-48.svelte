<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3x_bcqz.css';
import '../../css/f/fyq898vwm.css';
import '../../css/v/vst_-y9mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw3x_bcqz"/><path class="fyq898vwm"/><path class="vst_-y9mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-source-48" {...props}></Icon>
