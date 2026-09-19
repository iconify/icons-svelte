<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxoud4tuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxoud4tuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-coil" {...props}></Icon>
