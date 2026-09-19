<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6n4bfy8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6n4bfy8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:book-open-16-solid" {...props}></Icon>
