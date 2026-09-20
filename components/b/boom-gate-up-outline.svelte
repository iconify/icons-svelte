<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck1syfznr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck1syfznr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boom-gate-up-outline" {...props}></Icon>
