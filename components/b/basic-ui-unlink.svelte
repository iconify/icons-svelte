<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3t8i6bmf.css';
import '../../css/a/aa-24kbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x3t8i6bmf"/><path class="aa-24kbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-unlink" {...props}></Icon>
