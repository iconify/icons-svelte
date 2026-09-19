<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3_unr4bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3_unr4bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:feed" {...props}></Icon>
