<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx0cgwb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rx0cgwb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bird-scepter" {...props}></Icon>
