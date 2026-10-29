<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0sdpmbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0sdpmbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:laptop" {...props}></Icon>
