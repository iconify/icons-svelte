<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0pnj58ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="u0pnj58ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:error-alt" {...props}></Icon>
