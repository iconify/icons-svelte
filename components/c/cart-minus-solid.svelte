<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0-s0sb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0-s0sb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cart-minus-solid" {...props}></Icon>
