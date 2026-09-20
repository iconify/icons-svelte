<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed5-32ims.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5-32ims"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-line" {...props}></Icon>
