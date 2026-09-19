<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tza7uacyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tza7uacyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-left-05" {...props}></Icon>
