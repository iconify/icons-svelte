<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8sj8sifg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8sj8sifg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-tree" {...props}></Icon>
