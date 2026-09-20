<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndzyi9kfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndzyi9kfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:d3" {...props}></Icon>
