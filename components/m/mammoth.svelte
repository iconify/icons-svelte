<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odhxa5e7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odhxa5e7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mammoth" {...props}></Icon>
