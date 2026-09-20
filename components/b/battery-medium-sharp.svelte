<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mljm37bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mljm37bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-medium-sharp" {...props}></Icon>
