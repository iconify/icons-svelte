<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtfcq9iub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jtfcq9iub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:file-new" {...props}></Icon>
