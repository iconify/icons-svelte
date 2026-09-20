<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atusk1b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="atusk1b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-burger-on-bun" {...props}></Icon>
