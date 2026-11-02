<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2iofp4uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2iofp4uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-2-line" {...props}></Icon>
