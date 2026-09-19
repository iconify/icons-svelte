<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyp1_ed3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yyp1_ed3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:doge" {...props}></Icon>
