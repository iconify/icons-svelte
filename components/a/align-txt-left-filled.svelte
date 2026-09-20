<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj4f5jigr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gj4f5jigr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-left-filled" {...props}></Icon>
