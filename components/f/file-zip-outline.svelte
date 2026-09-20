<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfijv-8ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yfijv-8ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-zip-outline" {...props}></Icon>
