<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy1wcmb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy1wcmb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:network-alert" {...props}></Icon>
