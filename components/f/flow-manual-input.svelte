<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltl30k2-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltl30k2-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-input" {...props}></Icon>
