<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzvbmsb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xzvbmsb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fingers-crossed" {...props}></Icon>
