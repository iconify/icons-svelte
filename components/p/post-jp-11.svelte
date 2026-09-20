<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b95q12b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b95q12b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:post-jp-11" {...props}></Icon>
