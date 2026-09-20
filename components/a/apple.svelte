<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgk1m0ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhgk1m0ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apple" {...props}></Icon>
