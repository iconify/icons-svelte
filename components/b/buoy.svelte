<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogv16_bqf.css';
import '../../css/d/djjdvpbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogv16_bqf"/><path class="djjdvpbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:buoy" {...props}></Icon>
