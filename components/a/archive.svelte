<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb7_-3bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb7_-3bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:archive" {...props}></Icon>
