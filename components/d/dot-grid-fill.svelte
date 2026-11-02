<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fir_e1b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fir_e1b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dot-grid-fill" {...props}></Icon>
