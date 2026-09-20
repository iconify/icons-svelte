<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0biiu03p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="a0biiu03p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:marker-11" {...props}></Icon>
