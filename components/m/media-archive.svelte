<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojii0mt5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojii0mt5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:media-archive" {...props}></Icon>
