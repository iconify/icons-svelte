<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a04lmzz9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a04lmzz9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-left-solid" {...props}></Icon>
