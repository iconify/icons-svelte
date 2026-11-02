<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orkb68b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orkb68b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-lock-line" {...props}></Icon>
