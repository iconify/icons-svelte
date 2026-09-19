<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxk61cbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxk61cbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chaingun" {...props}></Icon>
