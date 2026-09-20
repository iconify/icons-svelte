<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owc77-wfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owc77-wfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-right" {...props}></Icon>
