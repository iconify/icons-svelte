<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cut-_vbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cut-_vbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hospital-fill-round" {...props}></Icon>
