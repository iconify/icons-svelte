<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1qpk_20w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1qpk_20w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-devices" {...props}></Icon>
