<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw2r4irnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zw2r4irnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-quora" {...props}></Icon>
