<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl32-54lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xl32-54lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:city-gate" {...props}></Icon>
