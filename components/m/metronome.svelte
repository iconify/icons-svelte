<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmt7afbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rmt7afbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:metronome" {...props}></Icon>
