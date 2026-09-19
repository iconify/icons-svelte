<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pll558mvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="pll558mvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:forkcms" {...props}></Icon>
