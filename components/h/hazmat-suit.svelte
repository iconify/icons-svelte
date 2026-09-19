<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1r8egb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1r8egb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hazmat-suit" {...props}></Icon>
