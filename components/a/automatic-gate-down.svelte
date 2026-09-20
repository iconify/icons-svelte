<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt_o3lb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_o3lb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:automatic-gate-down" {...props}></Icon>
