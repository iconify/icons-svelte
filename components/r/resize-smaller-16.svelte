<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhv8_vmwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhv8_vmwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:resize-smaller-16" {...props}></Icon>
