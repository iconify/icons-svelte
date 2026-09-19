<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0ql4n47b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0ql4n47b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dandelion-flower" {...props}></Icon>
