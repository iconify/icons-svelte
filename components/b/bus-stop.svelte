<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s42ri5_-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s42ri5_-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bus-stop" {...props}></Icon>
