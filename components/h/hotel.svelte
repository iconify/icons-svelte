<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkr3lbb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkr3lbb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hotel" {...props}></Icon>
