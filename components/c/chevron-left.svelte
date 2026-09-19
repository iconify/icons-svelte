<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5uwnpqzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u5uwnpqzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:chevron-left" {...props}></Icon>
