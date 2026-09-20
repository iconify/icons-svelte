<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8sv8yyko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8sv8yyko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bomb" {...props}></Icon>
