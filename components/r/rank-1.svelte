<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-6io26x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw-6io26x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rank-1" {...props}></Icon>
