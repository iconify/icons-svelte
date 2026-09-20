<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1te_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1te_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-k-circle" {...props}></Icon>
