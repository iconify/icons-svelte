<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uli4gbhou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uli4gbhou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:magnet" {...props}></Icon>
