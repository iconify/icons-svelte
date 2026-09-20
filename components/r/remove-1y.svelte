<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs4ym0b3p.css';
import '../../css/d/dp1f6j7dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="bs4ym0b3p"/><path class="dp1f6j7dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:remove-1y" {...props}></Icon>
