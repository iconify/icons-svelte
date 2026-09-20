<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5h712et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ep5h712et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bottles" {...props}></Icon>
