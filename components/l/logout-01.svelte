<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_tn_bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az_tn_bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logout-01" {...props}></Icon>
