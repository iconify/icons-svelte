<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs3t96b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3t96b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ar-solid" {...props}></Icon>
