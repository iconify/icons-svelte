<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_el_48wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_el_48wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-minus-solid" {...props}></Icon>
