<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/selg7tbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="selg7tbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-026" {...props}></Icon>
