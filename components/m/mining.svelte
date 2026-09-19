<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc3ewx6xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jc3ewx6xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mining" {...props}></Icon>
