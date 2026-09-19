<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xacu0mbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xacu0mbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-breath" {...props}></Icon>
