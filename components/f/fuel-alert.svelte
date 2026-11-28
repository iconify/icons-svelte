<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2ebaiu3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ebaiu3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fuel-alert" {...props}></Icon>
