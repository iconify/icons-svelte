<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhf158btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hhf158btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:linechart" {...props}></Icon>
