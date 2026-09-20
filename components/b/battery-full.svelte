<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqwqqcbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sqwqqcbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:battery-full" {...props}></Icon>
