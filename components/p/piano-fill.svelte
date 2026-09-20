<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bskn5pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-bskn5pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:piano-fill" {...props}></Icon>
