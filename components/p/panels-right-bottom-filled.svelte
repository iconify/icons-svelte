<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gch9l5uyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gch9l5uyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panels-right-bottom-filled" {...props}></Icon>
