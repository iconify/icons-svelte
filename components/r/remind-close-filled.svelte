<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x44ki8bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x44ki8bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:remind-close-filled" {...props}></Icon>
