<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv2c4yb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wv2c4yb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-wings" {...props}></Icon>
