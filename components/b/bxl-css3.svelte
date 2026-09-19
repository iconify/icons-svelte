<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opqkb-jvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opqkb-jvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-css3" {...props}></Icon>
