<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhrtpqbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhrtpqbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:continuity-below" {...props}></Icon>
