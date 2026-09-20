<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyir6uuhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yyir6uuhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:penny-arcade" {...props}></Icon>
