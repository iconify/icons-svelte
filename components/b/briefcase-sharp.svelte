<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tipf2-b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tipf2-b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:briefcase-sharp" {...props}></Icon>
