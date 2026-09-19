<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd583-bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="qd583-bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-text-o" {...props}></Icon>
