<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmgx3nbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmgx3nbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cart-plus" {...props}></Icon>
