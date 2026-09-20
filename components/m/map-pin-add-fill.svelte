<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sghtszopb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sghtszopb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-add-fill" {...props}></Icon>
