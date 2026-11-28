<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzmfcm04q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzmfcm04q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calculator" {...props}></Icon>
