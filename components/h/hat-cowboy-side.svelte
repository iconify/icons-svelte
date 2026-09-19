<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtjs7gb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xtjs7gb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hat-cowboy-side" {...props}></Icon>
