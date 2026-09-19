<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6wy2hb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6wy2hb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-down-sharp" {...props}></Icon>
