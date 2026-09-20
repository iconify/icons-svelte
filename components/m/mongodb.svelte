<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2uo6yruu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2uo6yruu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mongodb" {...props}></Icon>
