<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r76f4fxbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r76f4fxbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cart-flatbed-suitcase" {...props}></Icon>
