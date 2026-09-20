<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo7f0lbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uo7f0lbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:cog" {...props}></Icon>
