<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyji96b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyji96b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-gift" {...props}></Icon>
