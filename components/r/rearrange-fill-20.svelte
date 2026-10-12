<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sruzenvtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sruzenvtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rearrange-fill-20" {...props}></Icon>
