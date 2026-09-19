<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6l094dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq6l094dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-002" {...props}></Icon>
