<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx-evhbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx-evhbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dollar-usd" {...props}></Icon>
