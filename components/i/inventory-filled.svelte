<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c19up3bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c19up3bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:inventory-filled" {...props}></Icon>
