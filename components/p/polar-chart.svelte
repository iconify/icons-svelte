<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na0pki01k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na0pki01k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:polar-chart" {...props}></Icon>
