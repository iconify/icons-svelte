<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj5nrubhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xj5nrubhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:parking-bicycle-14" {...props}></Icon>
