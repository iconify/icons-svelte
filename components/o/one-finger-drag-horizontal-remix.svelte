<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuw6ebbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iuw6ebbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-drag-horizontal-remix" {...props}></Icon>
