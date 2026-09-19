<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcwzlqb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vcwzlqb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-right-circle" {...props}></Icon>
