<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8thah3mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q8thah3mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:continuity-above" {...props}></Icon>
