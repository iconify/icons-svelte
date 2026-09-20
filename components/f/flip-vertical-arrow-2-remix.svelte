<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e14wadjqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e14wadjqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flip-vertical-arrow-2-remix" {...props}></Icon>
