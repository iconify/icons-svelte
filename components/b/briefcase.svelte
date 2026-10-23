<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idr5ew13n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idr5ew13n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:briefcase" {...props}></Icon>
