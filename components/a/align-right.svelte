<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_w79bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o2_w79bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:align-right" {...props}></Icon>
