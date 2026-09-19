<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyt-vk_ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyt-vk_ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kebab-spit" {...props}></Icon>
