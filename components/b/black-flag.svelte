<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja5en4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ja5en4bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:black-flag" {...props}></Icon>
