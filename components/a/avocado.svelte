<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neirp7okh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neirp7okh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:avocado" {...props}></Icon>
