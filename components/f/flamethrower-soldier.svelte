<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed2g01b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ed2g01b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flamethrower-soldier" {...props}></Icon>
