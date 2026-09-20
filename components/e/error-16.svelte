<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7y1xq4zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b7y1xq4zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:error-16" {...props}></Icon>
