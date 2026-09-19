<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgfirvb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgfirvb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-042" {...props}></Icon>
