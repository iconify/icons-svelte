<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufw7ugvlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufw7ugvlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bus-clock" {...props}></Icon>
