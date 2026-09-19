<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwp11_b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwp11_b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-ccw" {...props}></Icon>
