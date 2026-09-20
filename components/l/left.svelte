<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyc-mbcsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yyc-mbcsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:left" {...props}></Icon>
