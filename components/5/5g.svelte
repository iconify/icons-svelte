<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km9-o-bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km9-o-bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:5g" {...props}></Icon>
