<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8a8omblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y8a8omblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:home" {...props}></Icon>
