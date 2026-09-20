<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl-lz1bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-lz1bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pwa" {...props}></Icon>
