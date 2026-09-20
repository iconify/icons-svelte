<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7i6l95g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cb7i6l95g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-visa" {...props}></Icon>
