<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5g6_n8oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5g6_n8oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laurel-wreath-right-filled" {...props}></Icon>
