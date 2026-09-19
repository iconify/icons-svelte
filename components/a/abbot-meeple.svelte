<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrs8idbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrs8idbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abbot-meeple" {...props}></Icon>
