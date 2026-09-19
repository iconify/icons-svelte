<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktswjabgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ktswjabgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-error-stroke-16" {...props}></Icon>
