<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2fyb_baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2fyb_baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-upload" {...props}></Icon>
