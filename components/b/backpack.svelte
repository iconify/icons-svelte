<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnoc_cc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fnoc_cc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:backpack" {...props}></Icon>
