<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_qo1duhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_qo1duhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-3-spades" {...props}></Icon>
