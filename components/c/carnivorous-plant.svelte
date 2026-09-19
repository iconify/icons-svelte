<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgf5uvnvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgf5uvnvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:carnivorous-plant" {...props}></Icon>
