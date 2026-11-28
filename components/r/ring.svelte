<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf25pihft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf25pihft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ring" {...props}></Icon>
