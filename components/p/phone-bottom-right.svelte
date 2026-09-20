<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp7zg1bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sp7zg1bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-bottom-right" {...props}></Icon>
