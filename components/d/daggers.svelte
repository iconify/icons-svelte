<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jncd0gk1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jncd0gk1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:daggers" {...props}></Icon>
