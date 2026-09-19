<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuwtgtn5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zuwtgtn5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:events-alt" {...props}></Icon>
