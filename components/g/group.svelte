<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nef5l-igr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nef5l-igr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:group" {...props}></Icon>
