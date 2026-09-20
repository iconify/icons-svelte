<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esb7-8xxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esb7-8xxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-scan-line" {...props}></Icon>
