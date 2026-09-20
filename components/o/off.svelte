<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4p4i2bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y4p4i2bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:off" {...props}></Icon>
