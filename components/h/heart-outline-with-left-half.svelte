<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcb7n_v4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lcb7n_v4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-outline-with-left-half" {...props}></Icon>
