<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2dcagbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2dcagbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:add-filled" {...props}></Icon>
