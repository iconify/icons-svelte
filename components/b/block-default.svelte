<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxbev_bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cxbev_bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:block-default" {...props}></Icon>
