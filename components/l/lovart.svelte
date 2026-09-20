<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0nf3sbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0nf3sbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lovart" {...props}></Icon>
