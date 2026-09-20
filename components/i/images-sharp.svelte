<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avz7zhbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avz7zhbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:images-sharp" {...props}></Icon>
