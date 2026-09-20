<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu6h-abma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu6h-abma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reactos" {...props}></Icon>
