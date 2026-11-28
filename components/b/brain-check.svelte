<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thfl-dbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thfl-dbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:brain-check" {...props}></Icon>
