<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo8se23fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo8se23fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-c" {...props}></Icon>
