<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlz96e2cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlz96e2cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cyclops" {...props}></Icon>
