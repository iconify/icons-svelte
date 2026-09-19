<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_jrl98rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_jrl98rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-118" {...props}></Icon>
