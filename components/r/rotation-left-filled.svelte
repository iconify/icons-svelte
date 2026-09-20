<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uottdfb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uottdfb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rotation-left-filled" {...props}></Icon>
