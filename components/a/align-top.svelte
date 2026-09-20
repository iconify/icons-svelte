<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4dneib8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4dneib8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-top" {...props}></Icon>
