<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm3tprbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm3tprbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-2-fill" {...props}></Icon>
