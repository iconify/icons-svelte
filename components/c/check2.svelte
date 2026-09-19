<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1s-4pk-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y1s-4pk-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:check2" {...props}></Icon>
