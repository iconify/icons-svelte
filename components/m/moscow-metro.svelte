<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikm53ybyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikm53ybyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:moscow-metro" {...props}></Icon>
