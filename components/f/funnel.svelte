<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g68wk6bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g68wk6bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:funnel" {...props}></Icon>
