<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kah0nub8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kah0nub8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pac-man" {...props}></Icon>
