<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lydunhi0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lydunhi0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:repeat-16" {...props}></Icon>
