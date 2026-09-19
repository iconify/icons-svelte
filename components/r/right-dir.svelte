<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bntc-zdzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":529,"height":1000};
const content = `<path class="bntc-zdzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:right-dir" {...props}></Icon>
