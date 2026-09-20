<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6kt0sa7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6kt0sa7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coffee-maker-outline" {...props}></Icon>
