<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo9fgqb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bo9fgqb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:double-arrow-left-filled" {...props}></Icon>
