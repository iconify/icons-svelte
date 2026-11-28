<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t37l2vbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t37l2vbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-lock-solid" {...props}></Icon>
