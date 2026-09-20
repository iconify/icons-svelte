<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vshk2dbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vshk2dbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:debug-16" {...props}></Icon>
