<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx1ugx-4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hx1ugx-4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hearing-disabled" {...props}></Icon>
