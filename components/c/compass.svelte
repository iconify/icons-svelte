<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upq_ys5ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="upq_ys5ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:compass" {...props}></Icon>
