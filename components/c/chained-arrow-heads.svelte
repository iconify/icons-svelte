<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6qk83b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6qk83b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chained-arrow-heads" {...props}></Icon>
