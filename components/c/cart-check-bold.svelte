<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9k6hn1ym.css';
import '../../css/u/ujd91437t.css';
import '../../css/d/d6h3j5b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9k6hn1ym"/><path class="ujd91437t"/><path class="d6h3j5b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-check-bold" {...props}></Icon>
