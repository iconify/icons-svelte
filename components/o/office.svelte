<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7f7z9bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m7f7z9bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:office" {...props}></Icon>
