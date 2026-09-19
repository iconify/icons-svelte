<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqbjcmbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zqbjcmbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:die-four" {...props}></Icon>
