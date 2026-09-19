<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyy7pdbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fyy7pdbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fairy" {...props}></Icon>
