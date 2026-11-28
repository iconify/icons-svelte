<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0b00-bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0b00-bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-sigma-solid" {...props}></Icon>
