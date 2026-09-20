<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auu_2cchm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="auu_2cchm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:globe" {...props}></Icon>
