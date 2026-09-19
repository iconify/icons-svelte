<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctyxlqbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctyxlqbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fan-light" {...props}></Icon>
