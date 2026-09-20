<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5x-zjtyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j5x-zjtyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:magic-wand-2-remix" {...props}></Icon>
