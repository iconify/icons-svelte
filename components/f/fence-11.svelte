<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egyn5sb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="egyn5sb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fence-11" {...props}></Icon>
