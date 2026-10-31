<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjbxpdbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjbxpdbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-snow-fill-round" {...props}></Icon>
