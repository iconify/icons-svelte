<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klsy0h-si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="klsy0h-si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:party-flags" {...props}></Icon>
