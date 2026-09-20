<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w52tpizdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w52tpizdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-new-line" {...props}></Icon>
