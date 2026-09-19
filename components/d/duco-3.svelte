<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7bct-bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7bct-bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:duco-3" {...props}></Icon>
