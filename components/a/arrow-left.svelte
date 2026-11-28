<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6rg17h4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rg17h4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-left" {...props}></Icon>
