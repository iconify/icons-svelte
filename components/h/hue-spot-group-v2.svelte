<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr9ok6bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr9ok6bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hue-spot-group-v2" {...props}></Icon>
