<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvyp8lo5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvyp8lo5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layers" {...props}></Icon>
