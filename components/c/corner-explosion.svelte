<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnozcpbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnozcpbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:corner-explosion" {...props}></Icon>
