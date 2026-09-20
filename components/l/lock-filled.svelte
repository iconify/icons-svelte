<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsb_3sb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tsb_3sb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:lock-filled" {...props}></Icon>
