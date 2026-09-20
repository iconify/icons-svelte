<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxprkbcka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxprkbcka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:github-alt" {...props}></Icon>
