<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt0ef04zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lt0ef04zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:briefcase-info" {...props}></Icon>
