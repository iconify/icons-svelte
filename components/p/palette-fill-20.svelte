<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pct7qxr4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pct7qxr4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:palette-fill-20" {...props}></Icon>
