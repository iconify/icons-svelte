<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyc9_1b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyc9_1b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:anarchy" {...props}></Icon>
