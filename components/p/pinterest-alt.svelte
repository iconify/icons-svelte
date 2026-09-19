<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-h1p6yyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-h1p6yyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:pinterest-alt" {...props}></Icon>
