<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy4c3lcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txy4c3lcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bank" {...props}></Icon>
