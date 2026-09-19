<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucm_evpsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucm_evpsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:laptop-code-outline" {...props}></Icon>
