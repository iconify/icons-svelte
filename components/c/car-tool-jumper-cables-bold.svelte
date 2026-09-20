<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utv3gdowh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utv3gdowh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-tool-jumper-cables-bold" {...props}></Icon>
