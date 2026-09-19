<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q010x0b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q010x0b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:butterfly-warning" {...props}></Icon>
