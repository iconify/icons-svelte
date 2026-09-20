<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx588wb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xx588wb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:greek-cross-in-box" {...props}></Icon>
