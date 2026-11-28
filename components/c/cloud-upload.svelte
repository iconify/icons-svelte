<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d65dfhbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d65dfhbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-upload" {...props}></Icon>
