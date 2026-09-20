<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttzr14bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ttzr14bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bar-code-outline" {...props}></Icon>
