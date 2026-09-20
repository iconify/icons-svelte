<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxwnozyd.css';
import '../../css/j/j5s8mp-8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="txxwnozyd"/><path class="j5s8mp-8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:movie" {...props}></Icon>
