<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqas8j_5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bqas8j_5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-build" {...props}></Icon>
