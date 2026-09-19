<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w09pfms2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w09pfms2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-shelter" {...props}></Icon>
