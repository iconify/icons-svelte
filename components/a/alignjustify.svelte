<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfg8bo1tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="cfg8bo1tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignjustify" {...props}></Icon>
