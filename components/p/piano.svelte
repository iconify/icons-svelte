<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzt8clmuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzt8clmuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:piano" {...props}></Icon>
