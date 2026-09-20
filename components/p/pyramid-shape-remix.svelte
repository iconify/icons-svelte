<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3z4r79fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3z4r79fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pyramid-shape-remix" {...props}></Icon>
