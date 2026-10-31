<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roahvb2is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roahvb2is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-instance-fill-round" {...props}></Icon>
