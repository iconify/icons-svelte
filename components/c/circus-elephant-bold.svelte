<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uek5jjtrg.css';
import '../../css/p/psb-p714j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uek5jjtrg"/><path class="psb-p714j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:circus-elephant-bold" {...props}></Icon>
