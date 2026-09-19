<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwkfy_b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwkfy_b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hound" {...props}></Icon>
