<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql8oqjbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ql8oqjbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pointer-filled" {...props}></Icon>
