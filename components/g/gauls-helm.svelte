<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksd02ccdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksd02ccdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gauls-helm" {...props}></Icon>
