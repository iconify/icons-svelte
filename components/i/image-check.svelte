<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zphfr0bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zphfr0bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-check" {...props}></Icon>
