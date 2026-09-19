<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afu2d_v6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afu2d_v6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bezier" {...props}></Icon>
