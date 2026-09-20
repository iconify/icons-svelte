<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsday64ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zsday64ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:batch-check-filled" {...props}></Icon>
