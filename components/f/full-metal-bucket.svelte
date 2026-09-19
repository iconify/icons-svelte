<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpd_n5uta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kpd_n5uta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-metal-bucket" {...props}></Icon>
