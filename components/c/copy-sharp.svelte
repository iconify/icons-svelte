<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3q84tbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3q84tbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:copy-sharp" {...props}></Icon>
