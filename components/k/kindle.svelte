<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccyd1l15x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccyd1l15x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kindle" {...props}></Icon>
