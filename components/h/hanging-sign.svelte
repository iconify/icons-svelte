<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te4ap0b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="te4ap0b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hanging-sign" {...props}></Icon>
