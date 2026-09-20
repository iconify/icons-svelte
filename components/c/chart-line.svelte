<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzj5ptbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzj5ptbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chart-line" {...props}></Icon>
