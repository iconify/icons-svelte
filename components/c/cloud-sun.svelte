<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ocapbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x3ocapbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sun" {...props}></Icon>
