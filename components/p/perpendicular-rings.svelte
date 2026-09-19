<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2m1wbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pp2m1wbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perpendicular-rings" {...props}></Icon>
