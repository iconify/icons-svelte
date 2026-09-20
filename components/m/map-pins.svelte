<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul8_q0b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8_q0b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-pins" {...props}></Icon>
