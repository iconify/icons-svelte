<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq2r9vbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lq2r9vbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:checkbox-filled" {...props}></Icon>
