<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgjuq208s.css';
import '../../css/u/u5frof2_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgjuq208s"/><path class="u5frof2_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-right-bold" {...props}></Icon>
