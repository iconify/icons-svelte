<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud5ss4a1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ud5ss4a1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:list-columns-reverse" {...props}></Icon>
