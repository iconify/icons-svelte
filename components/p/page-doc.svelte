<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd4fpfb_f.css';
import '../../css/b/b337xtreo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fd4fpfb_f"/><path class="b337xtreo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-doc" {...props}></Icon>
