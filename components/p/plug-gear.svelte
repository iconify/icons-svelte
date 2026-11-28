<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndvy_ubls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndvy_ubls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plug-gear" {...props}></Icon>
