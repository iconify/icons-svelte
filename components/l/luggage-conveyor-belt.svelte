<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzpbyf_rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzpbyf_rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:luggage-conveyor-belt" {...props}></Icon>
