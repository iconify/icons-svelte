<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8y2-tvlr.css';
import '../../css/q/qzm6rmb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8y2-tvlr"/><path class="qzm6rmb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-bold-duotone" {...props}></Icon>
