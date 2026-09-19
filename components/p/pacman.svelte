<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irci322_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="irci322_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pacman" {...props}></Icon>
