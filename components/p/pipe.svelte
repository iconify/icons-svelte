<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dumluac4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dumluac4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pipe" {...props}></Icon>
