<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6quovps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd6quovps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:backbone-shell" {...props}></Icon>
