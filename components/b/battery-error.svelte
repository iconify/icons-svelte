<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag11jn0th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ag11jn0th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-error" {...props}></Icon>
