<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv9wz8bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kv9wz8bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:door-handle" {...props}></Icon>
