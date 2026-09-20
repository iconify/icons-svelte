<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiw9x1boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="aiw9x1boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cart-minus-solid" {...props}></Icon>
