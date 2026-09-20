<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sedqzzbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sedqzzbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:ellipsis-vertical" {...props}></Icon>
