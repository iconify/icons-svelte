<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ostgxng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1027};
const content = `<path class="u4ostgxng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpeny" {...props}></Icon>
