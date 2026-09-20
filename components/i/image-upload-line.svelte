<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwmj_e-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwmj_e-pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-upload-line" {...props}></Icon>
