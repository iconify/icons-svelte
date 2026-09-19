<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1liorbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1360,"height":1000};
const content = `<path class="c1liorbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:picture" {...props}></Icon>
