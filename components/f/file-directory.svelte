<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysna8hi8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="ysna8hi8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory" {...props}></Icon>
