<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gau26bbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gau26bbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:crown" {...props}></Icon>
