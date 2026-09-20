<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf6zbp2gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf6zbp2gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-dashboard-lights-bold" {...props}></Icon>
