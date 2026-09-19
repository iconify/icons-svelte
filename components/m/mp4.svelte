<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9qfgabsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l9qfgabsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mp4" {...props}></Icon>
