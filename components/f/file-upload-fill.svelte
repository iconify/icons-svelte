<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/indfb2voo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="indfb2voo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-upload-fill" {...props}></Icon>
