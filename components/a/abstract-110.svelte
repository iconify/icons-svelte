<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxzx2mk3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxzx2mk3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-110" {...props}></Icon>
