<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q938jdcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q938jdcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-diamond-solid" {...props}></Icon>
