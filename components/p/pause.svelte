<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbl164bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbl164bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pause" {...props}></Icon>
