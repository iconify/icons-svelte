<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g496ggrfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g496ggrfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heptagram" {...props}></Icon>
