<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdhsskb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdhsskb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coral" {...props}></Icon>
