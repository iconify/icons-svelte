<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wey83sbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wey83sbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-flood" {...props}></Icon>
