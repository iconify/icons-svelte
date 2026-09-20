<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/a/azr-0u.css';
import '../../css/l/li54_l.css';
import '../../css/s/s0k_kc.css';
import '../../css/k/kr24cs.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c azr-0u"/><path class="a0m25c li54_l"/><path class="a0m25c s0k_kc"/><path class="a0m25c kr24cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:medical-services" {...props}></Icon>
