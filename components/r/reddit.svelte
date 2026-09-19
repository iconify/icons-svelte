<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61s8fx5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="r61s8fx5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:reddit" {...props}></Icon>
