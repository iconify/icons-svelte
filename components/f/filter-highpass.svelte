<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f62sy9bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f62sy9bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-highpass" {...props}></Icon>
