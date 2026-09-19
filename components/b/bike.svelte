<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ps7tb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":32};
const content = `<path class="e8ps7tb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:bike" {...props}></Icon>
