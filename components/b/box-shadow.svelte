<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3o8fhsot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3o8fhsot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-shadow" {...props}></Icon>
