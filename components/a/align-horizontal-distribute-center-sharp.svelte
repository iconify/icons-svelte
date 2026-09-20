<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iygen8b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iygen8b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-distribute-center-sharp" {...props}></Icon>
