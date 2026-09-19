<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiw5a_xxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eiw5a_xxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:goodreads-g" {...props}></Icon>
