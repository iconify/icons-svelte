<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy88w0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jy88w0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battleaxe" {...props}></Icon>
