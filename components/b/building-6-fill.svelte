<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m17m7eb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m17m7eb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-6-fill" {...props}></Icon>
