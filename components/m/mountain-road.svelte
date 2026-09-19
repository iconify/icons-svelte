<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsuh-fbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vsuh-fbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mountain-road" {...props}></Icon>
