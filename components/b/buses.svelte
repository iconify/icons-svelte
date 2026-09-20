<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwgzr4b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cwgzr4b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:buses" {...props}></Icon>
