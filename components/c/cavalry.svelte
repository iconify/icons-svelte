<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3scb1kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="if3scb1kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cavalry" {...props}></Icon>
