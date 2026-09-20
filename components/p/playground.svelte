<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7d_v9bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r7d_v9bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:playground" {...props}></Icon>
