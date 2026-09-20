<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj9exkbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj9exkbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-excel-2-line" {...props}></Icon>
