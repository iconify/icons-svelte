<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de472wbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de472wbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:hotel-bed-sharp" {...props}></Icon>
