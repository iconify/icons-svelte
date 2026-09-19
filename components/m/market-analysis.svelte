<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ekdu1_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ekdu1_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:market-analysis" {...props}></Icon>
