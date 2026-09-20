<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtj1kerrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtj1kerrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basketball-line" {...props}></Icon>
