<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijvvyibbs.css';
import '../../css/n/n_v2xfr4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ijvvyibbs"/><path class="n_v2xfr4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calendar-envelope" {...props}></Icon>
