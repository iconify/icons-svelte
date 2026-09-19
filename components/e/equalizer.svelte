<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvq0_nb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="yvq0_nb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:equalizer" {...props}></Icon>
