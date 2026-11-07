<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msp13vg8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msp13vg8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-brush-broken" {...props}></Icon>
