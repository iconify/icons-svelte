<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuu8dbcmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuu8dbcmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:move" {...props}></Icon>
