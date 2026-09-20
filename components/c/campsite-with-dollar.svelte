<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnmt3mb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mnmt3mb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-dollar" {...props}></Icon>
