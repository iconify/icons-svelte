<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7a-0fcly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7a-0fcly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cracked-mask" {...props}></Icon>
