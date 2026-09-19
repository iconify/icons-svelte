<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p59xlhsbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1472};
const content = `<g transform="translate(0 1472) scale(1 -1)"><path class="p59xlhsbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-down" {...props}></Icon>
