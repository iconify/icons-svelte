<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-be73b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m-be73b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-up-circle" {...props}></Icon>
