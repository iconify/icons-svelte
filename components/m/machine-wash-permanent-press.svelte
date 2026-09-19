<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6loahb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":456};
const content = `<path class="d6loahb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:machine-wash-permanent-press" {...props}></Icon>
