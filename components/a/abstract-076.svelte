<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibhn1269f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibhn1269f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-076" {...props}></Icon>
