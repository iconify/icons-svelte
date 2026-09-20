<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzc-a659z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gzc-a659z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ferryboat" {...props}></Icon>
