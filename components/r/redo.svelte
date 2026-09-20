<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glegu11ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="glegu11ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:redo" {...props}></Icon>
