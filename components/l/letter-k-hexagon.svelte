<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akwaxtv-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akwaxtv-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-hexagon" {...props}></Icon>
