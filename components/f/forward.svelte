<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grv2xbbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="grv2xbbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:forward" {...props}></Icon>
