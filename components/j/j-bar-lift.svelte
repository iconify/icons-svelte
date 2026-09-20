<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipg551bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ipg551bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:j-bar-lift" {...props}></Icon>
