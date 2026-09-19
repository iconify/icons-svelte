<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xytqzzb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xytqzzb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:molotov" {...props}></Icon>
