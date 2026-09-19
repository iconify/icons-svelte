<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2k8v2boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2k8v2boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-portal" {...props}></Icon>
