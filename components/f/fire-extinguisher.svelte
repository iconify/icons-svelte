<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxf74wbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxf74wbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fire-extinguisher" {...props}></Icon>
