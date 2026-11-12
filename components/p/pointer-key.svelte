<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo2-_7upc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo2-_7upc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-key" {...props}></Icon>
