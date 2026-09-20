<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln9qkabwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ln9qkabwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:natural-11" {...props}></Icon>
