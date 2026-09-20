<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw653obdk.css';
import '../../css/m/mhkxhvbuh.css';
import '../../css/a/a3iyb8b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bw653obdk"/><path class="mhkxhvbuh"/><path class="a3iyb8b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-vertical-ellipse" {...props}></Icon>
