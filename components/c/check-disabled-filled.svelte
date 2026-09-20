<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0dmxabkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z0dmxabkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:check-disabled-filled" {...props}></Icon>
