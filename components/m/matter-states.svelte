<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7wx8zbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7wx8zbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:matter-states" {...props}></Icon>
