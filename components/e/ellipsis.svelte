<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_tqropmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="b_tqropmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:ellipsis" {...props}></Icon>
