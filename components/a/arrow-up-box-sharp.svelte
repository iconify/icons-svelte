<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1qd13b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1qd13b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-up-box-sharp" {...props}></Icon>
