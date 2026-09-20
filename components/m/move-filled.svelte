<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brvnjmbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="brvnjmbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:move-filled" {...props}></Icon>
