<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwkkcb_dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwkkcb_dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:betterdiscord" {...props}></Icon>
