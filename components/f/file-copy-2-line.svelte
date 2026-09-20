<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4cghxbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4cghxbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-copy-2-line" {...props}></Icon>
