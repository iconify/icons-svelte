<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1bhhhb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s1bhhhb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:archive" {...props}></Icon>
