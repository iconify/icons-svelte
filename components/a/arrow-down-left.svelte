<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgoo95b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rgoo95b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-down-left" {...props}></Icon>
