<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idnx1mbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="idnx1mbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-invoice" {...props}></Icon>
