<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdhx6_hqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bdhx6_hqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:completed" {...props}></Icon>
