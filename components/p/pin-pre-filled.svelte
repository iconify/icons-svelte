<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js6a3cbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="js6a3cbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pin-pre-filled" {...props}></Icon>
