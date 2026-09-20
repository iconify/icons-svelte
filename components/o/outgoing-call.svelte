<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4l6tdyts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4l6tdyts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:outgoing-call" {...props}></Icon>
