<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs6qk0bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs6qk0bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-moon-solid" {...props}></Icon>
