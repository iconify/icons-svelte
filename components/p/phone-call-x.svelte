<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5dfn_bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5dfn_bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-call-x" {...props}></Icon>
