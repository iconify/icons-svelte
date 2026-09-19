<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs299dt7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vs299dt7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:heart" {...props}></Icon>
