<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-w0-5vki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-w0-5vki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:love-injection" {...props}></Icon>
