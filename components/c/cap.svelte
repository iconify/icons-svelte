<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a80-k7bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a80-k7bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cap" {...props}></Icon>
