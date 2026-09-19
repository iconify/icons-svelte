<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc8dg7beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="sc8dg7beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:campground" {...props}></Icon>
