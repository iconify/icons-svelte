<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te1q50b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te1q50b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-a-circle-outline" {...props}></Icon>
