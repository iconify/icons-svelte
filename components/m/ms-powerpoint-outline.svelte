<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt7s2fbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lt7s2fbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ms-powerpoint-outline" {...props}></Icon>
