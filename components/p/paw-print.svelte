<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noml167iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noml167iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:paw-print" {...props}></Icon>
