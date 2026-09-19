<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmpb39b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qmpb39b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:metadata-definition" {...props}></Icon>
