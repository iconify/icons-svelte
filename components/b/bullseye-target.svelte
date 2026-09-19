<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zor9lmbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zor9lmbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bullseye-target" {...props}></Icon>
