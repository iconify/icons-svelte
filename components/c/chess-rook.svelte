<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2t293-ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="g2t293-ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chess-rook" {...props}></Icon>
