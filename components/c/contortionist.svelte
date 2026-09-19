<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krucpwwea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krucpwwea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:contortionist" {...props}></Icon>
