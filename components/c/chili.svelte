<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgotcl4sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bgotcl4sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chili" {...props}></Icon>
