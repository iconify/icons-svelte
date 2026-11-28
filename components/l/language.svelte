<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khm7x6mgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khm7x6mgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:language" {...props}></Icon>
