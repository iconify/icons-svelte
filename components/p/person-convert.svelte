<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4wa76bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4wa76bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-convert" {...props}></Icon>
