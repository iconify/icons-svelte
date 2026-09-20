<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1uftcb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p1uftcb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:monorail" {...props}></Icon>
