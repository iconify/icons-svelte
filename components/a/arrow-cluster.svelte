<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cytbo59vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cytbo59vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrow-cluster" {...props}></Icon>
