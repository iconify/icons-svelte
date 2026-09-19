<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okaphv3fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="okaphv3fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:5-circle-fill" {...props}></Icon>
