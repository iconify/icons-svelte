<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zet6c8b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zet6c8b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-minus-filled" {...props}></Icon>
