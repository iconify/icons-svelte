<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo86ez2pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo86ez2pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-go-back-line" {...props}></Icon>
