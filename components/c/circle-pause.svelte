<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdt_johva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdt_johva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-pause" {...props}></Icon>
