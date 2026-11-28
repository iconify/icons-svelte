<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf7fidc9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf7fidc9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:backpack-check" {...props}></Icon>
