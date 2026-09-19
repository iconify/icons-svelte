<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2ujxbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht2ujxbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:monkey-wrench" {...props}></Icon>
