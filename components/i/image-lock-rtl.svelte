<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fizxgs--e.css';
import '../../css/d/dkx9jnbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fizxgs--e"/><path class="dkx9jnbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-lock-rtl" {...props}></Icon>
