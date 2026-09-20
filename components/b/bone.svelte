<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3rux0b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3rux0b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bone" {...props}></Icon>
