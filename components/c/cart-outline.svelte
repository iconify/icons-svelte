<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgpsmabvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgpsmabvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-outline" {...props}></Icon>
