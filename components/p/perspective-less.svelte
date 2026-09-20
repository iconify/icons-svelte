<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fusn3hbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fusn3hbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:perspective-less" {...props}></Icon>
