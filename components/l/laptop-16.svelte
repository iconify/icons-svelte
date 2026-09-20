<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3z9inily.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s3z9inily"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:laptop-16" {...props}></Icon>
