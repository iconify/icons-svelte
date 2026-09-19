<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3j2m0_dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3j2m0_dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-open-fill-16" {...props}></Icon>
