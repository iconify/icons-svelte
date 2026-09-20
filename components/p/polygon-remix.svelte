<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3eun504p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f3eun504p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polygon-remix" {...props}></Icon>
