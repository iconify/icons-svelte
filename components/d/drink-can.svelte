<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfs43dbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sfs43dbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:drink-can" {...props}></Icon>
