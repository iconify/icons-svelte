<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x03w4o6-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x03w4o6-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:give-gift-remix" {...props}></Icon>
