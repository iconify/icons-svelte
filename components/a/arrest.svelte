<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrbl_6kht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qrbl_6kht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrest" {...props}></Icon>
