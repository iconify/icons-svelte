<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9bqbb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we9bqbb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-plus" {...props}></Icon>
