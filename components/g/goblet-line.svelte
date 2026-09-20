<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dautg90hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dautg90hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:goblet-line" {...props}></Icon>
