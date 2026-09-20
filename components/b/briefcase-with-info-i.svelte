<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m28-rvb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m28-rvb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-info-i" {...props}></Icon>
