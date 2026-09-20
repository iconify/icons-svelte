<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_3_dhjxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3_dhjxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text-delete" {...props}></Icon>
