<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh77clr3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qh77clr3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:atom" {...props}></Icon>
