<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5nj3ibtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5nj3ibtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boom-gate-outline" {...props}></Icon>
