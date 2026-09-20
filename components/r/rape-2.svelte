<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe81y5u7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe81y5u7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rape-2" {...props}></Icon>
