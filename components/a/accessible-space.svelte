<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr_dv5t7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mr_dv5t7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:accessible-space" {...props}></Icon>
