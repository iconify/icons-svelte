<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibnhr6bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibnhr6bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rice-cooker" {...props}></Icon>
