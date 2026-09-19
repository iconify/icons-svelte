<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx_6pdo2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx_6pdo2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:institutional-building" {...props}></Icon>
