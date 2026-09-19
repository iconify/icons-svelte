<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol6f-pyhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ol6f-pyhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pretzel" {...props}></Icon>
