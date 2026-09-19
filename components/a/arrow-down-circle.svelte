<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttssy_8tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ttssy_8tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-circle" {...props}></Icon>
