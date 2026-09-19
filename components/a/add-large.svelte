<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxwc_zbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lxwc_zbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-large" {...props}></Icon>
