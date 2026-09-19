<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb3sqvbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fb3sqvbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cloudy-fork" {...props}></Icon>
