<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1v__7tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kd1v__7tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beer-stein" {...props}></Icon>
