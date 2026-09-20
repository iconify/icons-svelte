<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1m0s1bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o1m0s1bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bomb" {...props}></Icon>
