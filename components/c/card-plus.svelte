<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf530d1ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf530d1ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:card-plus" {...props}></Icon>
