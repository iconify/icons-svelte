<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqi4ufqbo.css';
import '../../css/y/ylqfvzsqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rqi4ufqbo"/><path class="ylqfvzsqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:nutrition-sharp" {...props}></Icon>
