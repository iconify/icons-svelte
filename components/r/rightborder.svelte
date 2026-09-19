<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en6iffg9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="en6iffg9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rightborder" {...props}></Icon>
