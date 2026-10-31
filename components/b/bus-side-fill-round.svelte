<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbrnwttpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbrnwttpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bus-side-fill-round" {...props}></Icon>
