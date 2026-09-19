<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8ou37b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="q8ou37b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:file-alt" {...props}></Icon>
