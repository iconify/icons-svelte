<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti80hsb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti80hsb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:box-solid" {...props}></Icon>
