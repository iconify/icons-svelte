<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il1_u-b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="il1_u-b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-horror-ghost" {...props}></Icon>
