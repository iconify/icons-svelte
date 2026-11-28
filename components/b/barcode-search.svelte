<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf0ujibzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf0ujibzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:barcode-search" {...props}></Icon>
