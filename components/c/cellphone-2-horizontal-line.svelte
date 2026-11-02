<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-1j1wbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-1j1wbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-horizontal-line" {...props}></Icon>
