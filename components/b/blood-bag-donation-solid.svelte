<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khn35wb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="khn35wb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:blood-bag-donation-solid" {...props}></Icon>
