<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uidu69k_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uidu69k_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-big-up" {...props}></Icon>
