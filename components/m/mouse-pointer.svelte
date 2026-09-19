<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9iw4fnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we9iw4fnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-pointer" {...props}></Icon>
