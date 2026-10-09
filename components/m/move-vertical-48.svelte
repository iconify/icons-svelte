<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh9opkozm.css';
import '../../css/d/dc1ph1bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jh9opkozm"/><path class="dc1ph1bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-vertical-48" {...props}></Icon>
