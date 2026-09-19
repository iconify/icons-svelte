<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3-ph0b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u3-ph0b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frozen-body" {...props}></Icon>
