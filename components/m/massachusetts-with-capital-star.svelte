<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slim3-b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="slim3-b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:massachusetts-with-capital-star" {...props}></Icon>
