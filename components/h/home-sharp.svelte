<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xowvf-_hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xowvf-_hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:home-sharp" {...props}></Icon>
