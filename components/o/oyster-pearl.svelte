<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn0gn1b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jn0gn1b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oyster-pearl" {...props}></Icon>
