<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5olcob6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5olcob6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flamer" {...props}></Icon>
