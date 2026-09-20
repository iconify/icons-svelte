<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws56w0zmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws56w0zmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-estate" {...props}></Icon>
