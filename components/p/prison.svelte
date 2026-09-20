<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frw75db4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="frw75db4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:prison" {...props}></Icon>
