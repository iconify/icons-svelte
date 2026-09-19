<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q97qiwbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="q97qiwbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:apple" {...props}></Icon>
