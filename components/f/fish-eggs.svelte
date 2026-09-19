<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i002w5bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i002w5bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fish-eggs" {...props}></Icon>
