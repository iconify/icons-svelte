<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6u-x48h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zz6u-x48h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:database-view" {...props}></Icon>
