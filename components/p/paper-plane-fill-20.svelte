<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj9rxse9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lj9rxse9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paper-plane-fill-20" {...props}></Icon>
