<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj3_jnb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cj3_jnb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-open-gabled-building-with-window" {...props}></Icon>
