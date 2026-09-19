<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_bmn1bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_bmn1bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:erlenmeyer" {...props}></Icon>
