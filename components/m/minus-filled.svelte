<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svq43ibny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="svq43ibny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:minus-filled" {...props}></Icon>
