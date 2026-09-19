<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ttx_b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9ttx_b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-009" {...props}></Icon>
