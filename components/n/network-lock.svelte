<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aksmz6bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aksmz6bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:network-lock" {...props}></Icon>
