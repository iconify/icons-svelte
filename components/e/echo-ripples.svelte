<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in4ro2qrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in4ro2qrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:echo-ripples" {...props}></Icon>
