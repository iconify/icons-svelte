<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x99r71mke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x99r71mke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mail4" {...props}></Icon>
