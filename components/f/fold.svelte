<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfex1wr8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="bfex1wr8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fold" {...props}></Icon>
