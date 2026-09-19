<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc-ok1ayh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zc-ok1ayh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:pixelfed" {...props}></Icon>
