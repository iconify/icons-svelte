<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3tz4sp-n.css';
import '../../css/a/ad2r2ebzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3tz4sp-n"/><path class="ad2r2ebzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:files-20-bold" {...props}></Icon>
