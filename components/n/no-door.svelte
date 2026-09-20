<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux5mhg-gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ux5mhg-gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:no-door" {...props}></Icon>
