<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz8d8p7vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz8d8p7vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:juniper-networks" {...props}></Icon>
