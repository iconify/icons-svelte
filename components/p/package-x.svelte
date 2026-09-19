<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d2fl3m4rd.css';
import '../../css/c/c2lq5wbok.css';
import '../../css/m/mjuiasbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d2fl3m4rd"/><path class="c2lq5wbok"/><path class="mjuiasbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-x" {...props}></Icon>
