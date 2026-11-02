<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c351c7shn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c351c7shn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horse-in-eaved-leanto-shelter" {...props}></Icon>
