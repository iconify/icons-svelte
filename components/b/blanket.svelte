<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9g-hpb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t9g-hpb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:blanket" {...props}></Icon>
