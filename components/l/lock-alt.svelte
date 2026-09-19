<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjlwor79m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yjlwor79m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:lock-alt" {...props}></Icon>
