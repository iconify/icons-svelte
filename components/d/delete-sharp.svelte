<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9-7gieeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9-7gieeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:delete-sharp" {...props}></Icon>
