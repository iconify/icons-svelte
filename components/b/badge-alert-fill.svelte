<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl8c9tblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl8c9tblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-alert-fill" {...props}></Icon>
