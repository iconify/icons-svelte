<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2z222b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2z222b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:neck-bite" {...props}></Icon>
