<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t93d48h6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t93d48h6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bluetooth-check" {...props}></Icon>
