<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuhnlh07d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xuhnlh07d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picture-outline" {...props}></Icon>
