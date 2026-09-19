<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iet_bbczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iet_bbczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plane-pilot" {...props}></Icon>
