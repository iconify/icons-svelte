<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoag9pb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="aoag9pb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-flood-water-circle-arrow-right" {...props}></Icon>
