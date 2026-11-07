<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkai44buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkai44buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-round-minimalistic-bold" {...props}></Icon>
