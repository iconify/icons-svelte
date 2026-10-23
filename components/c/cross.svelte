<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le7_c61zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le7_c61zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cross" {...props}></Icon>
