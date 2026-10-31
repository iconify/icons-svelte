<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2-5yub3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2-5yub3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-dot-fill-round" {...props}></Icon>
