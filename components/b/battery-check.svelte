<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn_cutbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_cutbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:battery-check" {...props}></Icon>
