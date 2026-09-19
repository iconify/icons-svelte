<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvh2v--5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="bvh2v--5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:link" {...props}></Icon>
