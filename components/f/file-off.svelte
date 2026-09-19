<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m80yhwbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m80yhwbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:file-off" {...props}></Icon>
