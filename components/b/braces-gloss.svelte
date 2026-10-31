<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh_b3mw3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh_b3mw3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:braces-gloss" {...props}></Icon>
