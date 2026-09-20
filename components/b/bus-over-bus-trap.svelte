<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffx7jjomr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ffx7jjomr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bus-over-bus-trap" {...props}></Icon>
