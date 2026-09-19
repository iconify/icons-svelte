<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zndv10soq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zndv10soq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-right-02" {...props}></Icon>
