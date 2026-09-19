<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtm7_qb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtm7_qb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-016" {...props}></Icon>
