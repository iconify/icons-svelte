<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6q5h5ycr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6q5h5ycr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-mongodb" {...props}></Icon>
