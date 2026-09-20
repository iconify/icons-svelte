<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g30601bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g30601bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-download-fill" {...props}></Icon>
