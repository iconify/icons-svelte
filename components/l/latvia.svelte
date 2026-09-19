<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxjhxqbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxjhxqbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:latvia" {...props}></Icon>
