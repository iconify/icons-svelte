<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbidn8bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xbidn8bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:optician-15" {...props}></Icon>
