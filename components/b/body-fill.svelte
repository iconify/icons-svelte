<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqe43nhdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqe43nhdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:body-fill" {...props}></Icon>
