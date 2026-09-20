<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dta6c0b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dta6c0b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map-pin" {...props}></Icon>
