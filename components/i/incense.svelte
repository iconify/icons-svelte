<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weh0b5bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="weh0b5bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:incense" {...props}></Icon>
