<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzgz5ob4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzgz5ob4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-down-solid" {...props}></Icon>
