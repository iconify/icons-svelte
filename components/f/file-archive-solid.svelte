<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfd8-93rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tfd8-93rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-archive-solid" {...props}></Icon>
