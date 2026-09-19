<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7q3lxb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7q3lxb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frozen-orb" {...props}></Icon>
