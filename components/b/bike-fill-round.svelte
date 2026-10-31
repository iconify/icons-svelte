<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-apdubfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-apdubfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bike-fill-round" {...props}></Icon>
