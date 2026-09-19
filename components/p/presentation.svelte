<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-8f8cbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-8f8cbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:presentation" {...props}></Icon>
