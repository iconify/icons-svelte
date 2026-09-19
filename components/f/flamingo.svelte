<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc-bqdg5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wc-bqdg5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flamingo" {...props}></Icon>
