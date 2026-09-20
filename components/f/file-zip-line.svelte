<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl-vz6ykx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl-vz6ykx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-zip-line" {...props}></Icon>
