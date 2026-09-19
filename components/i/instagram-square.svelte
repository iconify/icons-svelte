<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j88t_ybxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j88t_ybxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:instagram-square" {...props}></Icon>
