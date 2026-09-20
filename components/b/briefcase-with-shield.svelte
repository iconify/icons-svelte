<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm7kq5o3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sm7kq5o3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-shield" {...props}></Icon>
