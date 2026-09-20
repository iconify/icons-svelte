<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4r4dxvcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r4dxvcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-large2-filled" {...props}></Icon>
