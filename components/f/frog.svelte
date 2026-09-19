<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v54s_nbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="v54s_nbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:frog" {...props}></Icon>
