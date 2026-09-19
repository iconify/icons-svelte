<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra32g-kfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ra32g-kfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:body-height" {...props}></Icon>
