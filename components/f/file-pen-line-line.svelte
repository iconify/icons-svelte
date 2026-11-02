<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd69pcczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd69pcczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-pen-line-line" {...props}></Icon>
