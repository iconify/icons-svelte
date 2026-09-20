<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1nd1yxqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1nd1yxqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-download" {...props}></Icon>
