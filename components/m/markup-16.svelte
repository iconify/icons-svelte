<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_0nci75d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_0nci75d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:markup-16" {...props}></Icon>
