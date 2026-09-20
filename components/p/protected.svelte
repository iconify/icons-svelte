<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3ah-jjoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ah-jjoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:protected" {...props}></Icon>
