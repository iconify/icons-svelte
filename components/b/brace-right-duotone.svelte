<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4w3pb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zv4w3pb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brace-right-duotone" {...props}></Icon>
