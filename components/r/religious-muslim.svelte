<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucy9gabxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucy9gabxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-muslim" {...props}></Icon>
