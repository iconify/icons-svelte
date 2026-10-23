<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3-5t2bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3-5t2bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-column-increasing" {...props}></Icon>
