<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1m6anbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1m6anbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pinata" {...props}></Icon>
