<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3-ruybek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="s3-ruybek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:mic" {...props}></Icon>
