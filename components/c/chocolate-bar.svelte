<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly3zt6bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly3zt6bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chocolate-bar" {...props}></Icon>
