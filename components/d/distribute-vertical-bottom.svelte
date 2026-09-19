<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9bpb7vag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l9bpb7vag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:distribute-vertical-bottom" {...props}></Icon>
