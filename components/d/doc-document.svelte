<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r685v1blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r685v1blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:doc-document" {...props}></Icon>
