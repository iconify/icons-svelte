<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdd7vy8ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdd7vy8ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-up-dashed-panel" {...props}></Icon>
