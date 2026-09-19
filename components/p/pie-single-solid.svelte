<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5u-s0bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b5u-s0bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pie-single-solid" {...props}></Icon>
