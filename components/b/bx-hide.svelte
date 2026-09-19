<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfsjoy2pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfsjoy2pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-hide" {...props}></Icon>
