<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_7av-bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_7av-bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fish-corpse" {...props}></Icon>
