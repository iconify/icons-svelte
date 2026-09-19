<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t50t30biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t50t30biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rope-coil" {...props}></Icon>
