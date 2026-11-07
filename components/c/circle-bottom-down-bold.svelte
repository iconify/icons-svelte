<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj1s-63ya.css';
import '../../css/u/u2tnche2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj1s-63ya"/><path class="u2tnche2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-bottom-down-bold" {...props}></Icon>
