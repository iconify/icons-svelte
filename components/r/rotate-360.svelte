<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whars2o0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="whars2o0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-360" {...props}></Icon>
