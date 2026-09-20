<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jje7dnb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jje7dnb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:data-filled" {...props}></Icon>
