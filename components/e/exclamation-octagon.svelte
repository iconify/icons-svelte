<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb_m5_hnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb_m5_hnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:exclamation-octagon" {...props}></Icon>
