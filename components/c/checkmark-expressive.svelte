<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsfevtbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsfevtbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkmark-expressive" {...props}></Icon>
