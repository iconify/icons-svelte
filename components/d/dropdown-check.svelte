<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1j_wl62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1j_wl62j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dropdown-check" {...props}></Icon>
