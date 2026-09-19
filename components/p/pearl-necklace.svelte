<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4vn-2u8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4vn-2u8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pearl-necklace" {...props}></Icon>
