<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8iorx6kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8iorx6kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:level-end-flag" {...props}></Icon>
