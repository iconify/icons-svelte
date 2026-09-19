<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7_ctwb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m7_ctwb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:camp-cooking-pot" {...props}></Icon>
