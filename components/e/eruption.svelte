<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb3qe19hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb3qe19hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eruption" {...props}></Icon>
