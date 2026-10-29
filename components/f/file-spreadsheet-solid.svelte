<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_sx0ib-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_sx0ib-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-spreadsheet-solid" {...props}></Icon>
