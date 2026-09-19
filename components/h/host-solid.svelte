<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb-1labtg.css';
import '../../css/f/fp79t9bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="wb-1labtg"/><path class="fp79t9bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:host-solid" {...props}></Icon>
