<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg12si0rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg12si0rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-rain-wind" {...props}></Icon>
