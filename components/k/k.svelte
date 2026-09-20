<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw7hgimri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iw7hgimri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:k" {...props}></Icon>
