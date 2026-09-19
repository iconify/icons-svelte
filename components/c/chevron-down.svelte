<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sivxnq7wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sivxnq7wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-down" {...props}></Icon>
