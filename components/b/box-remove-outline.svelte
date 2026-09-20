<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwtfi1jsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwtfi1jsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-remove-outline" {...props}></Icon>
