<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evue-8bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evue-8bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:french-horn" {...props}></Icon>
