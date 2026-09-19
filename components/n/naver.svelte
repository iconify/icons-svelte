<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht-s7mkzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1632};
const content = `<path class="ht-s7mkzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:naver" {...props}></Icon>
