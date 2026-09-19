<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a94hj8blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a94hj8blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bowling-ball" {...props}></Icon>
