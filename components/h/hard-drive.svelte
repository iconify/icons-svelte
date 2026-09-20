<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um8k7-jvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um8k7-jvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hard-drive" {...props}></Icon>
