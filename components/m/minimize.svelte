<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg515_j0x.css';
import '../../css/g/go55dbb3w.css';
import '../../css/s/sr3x7wrjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="sg515_j0x"/><path class="go55dbb3w"/><path class="sr3x7wrjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:minimize" {...props}></Icon>
