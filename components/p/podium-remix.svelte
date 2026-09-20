<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl35iab1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hl35iab1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:podium-remix" {...props}></Icon>
