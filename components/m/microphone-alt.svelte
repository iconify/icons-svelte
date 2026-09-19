<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbr4szslo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="kbr4szslo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microphone-alt" {...props}></Icon>
