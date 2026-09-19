<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upv8a5aru.css';
import '../../css/y/y67djbpgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="upv8a5aru"/><path class="y67djbpgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location" {...props}></Icon>
