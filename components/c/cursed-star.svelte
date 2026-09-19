<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1kq5qb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1kq5qb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cursed-star" {...props}></Icon>
