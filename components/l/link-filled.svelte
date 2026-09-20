<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm0xz1bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tm0xz1bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:link-filled" {...props}></Icon>
