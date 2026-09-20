<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mozawhblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mozawhblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:octagram-shape-solid" {...props}></Icon>
