<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpg5sf9ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dpg5sf9ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:comet" {...props}></Icon>
