<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb_2p8blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb_2p8blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-portrait-filled" {...props}></Icon>
