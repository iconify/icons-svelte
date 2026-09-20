<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhzw_ibjg.css';
import '../../css/f/fudbgdb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":330};
const content = `<path class="uhzw_ibjg"/><path class="fudbgdb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hono" {...props}></Icon>
