<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqix46bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqix46bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:broadsword" {...props}></Icon>
