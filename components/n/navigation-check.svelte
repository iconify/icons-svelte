<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roys9q8ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roys9q8ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:navigation-check" {...props}></Icon>
