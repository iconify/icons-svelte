<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs13libeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs13libeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-arrow-down" {...props}></Icon>
