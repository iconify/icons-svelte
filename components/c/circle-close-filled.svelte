<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isok_lbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="isok_lbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-close-filled" {...props}></Icon>
