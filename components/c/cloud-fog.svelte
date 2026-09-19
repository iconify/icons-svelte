<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfqcq4bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dfqcq4bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-fog" {...props}></Icon>
