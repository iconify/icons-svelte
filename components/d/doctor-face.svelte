<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2thj4bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2thj4bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:doctor-face" {...props}></Icon>
