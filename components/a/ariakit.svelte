<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip1i70bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip1i70bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ariakit" {...props}></Icon>
