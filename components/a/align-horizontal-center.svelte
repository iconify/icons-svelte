<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elov1abin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="elov1abin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:align-horizontal-center" {...props}></Icon>
