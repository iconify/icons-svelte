<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okctgjbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okctgjbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-120" {...props}></Icon>
