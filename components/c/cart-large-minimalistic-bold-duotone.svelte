<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1mqiebea.css';
import '../../css/b/bqmrjvvdk.css';
import '../../css/x/xggr4mj5e.css';
import '../../css/n/npq7lzc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mqiebea"/><path class="bqmrjvvdk"/><path class="xggr4mj5e"/><path class="npq7lzc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-minimalistic-bold-duotone" {...props}></Icon>
