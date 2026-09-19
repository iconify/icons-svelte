<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceek4hbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceek4hbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:cloud-rain" {...props}></Icon>
