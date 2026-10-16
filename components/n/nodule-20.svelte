<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s89r-jghf.css';
import '../../css/z/ztpyv-0ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s89r-jghf"/><path class="ztpyv-0ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nodule-20" {...props}></Icon>
