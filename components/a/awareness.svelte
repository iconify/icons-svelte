<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzmhllkwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dzmhllkwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:awareness" {...props}></Icon>
