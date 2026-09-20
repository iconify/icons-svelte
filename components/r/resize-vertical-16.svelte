<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee0xevyio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ee0xevyio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:resize-vertical-16" {...props}></Icon>
