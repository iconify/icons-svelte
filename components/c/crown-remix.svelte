<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lae7oe6wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lae7oe6wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:crown-remix" {...props}></Icon>
