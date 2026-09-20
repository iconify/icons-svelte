<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0igmmbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":50,"top":-1};
const content = `<path class="a0igmmbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:php-dark" {...props}></Icon>
