<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccoa8rb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccoa8rb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:horizontal-slider-2-remix" {...props}></Icon>
