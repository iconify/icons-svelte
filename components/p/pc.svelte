<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9f86gbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t9f86gbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pc" {...props}></Icon>
