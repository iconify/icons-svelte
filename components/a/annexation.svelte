<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxt-t0hgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxt-t0hgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:annexation" {...props}></Icon>
