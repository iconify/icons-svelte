<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn2rp_bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pn2rp_bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meat" {...props}></Icon>
