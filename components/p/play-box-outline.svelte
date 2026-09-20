<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9oq99bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9oq99bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-outline" {...props}></Icon>
