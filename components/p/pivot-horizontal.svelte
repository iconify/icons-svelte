<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhomknb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vhomknb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pivot-horizontal" {...props}></Icon>
