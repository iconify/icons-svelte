<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po1ze2c7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="po1ze2c7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:helmet-un" {...props}></Icon>
