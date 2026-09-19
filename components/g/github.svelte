<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnydghbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="pnydghbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:github" {...props}></Icon>
