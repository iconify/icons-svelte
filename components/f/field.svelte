<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqdqj7gbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqdqj7gbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:field" {...props}></Icon>
