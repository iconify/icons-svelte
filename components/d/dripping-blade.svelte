<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzq_qbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwzq_qbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dripping-blade" {...props}></Icon>
