<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt0u17bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0u17bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:happy-heart-eyes" {...props}></Icon>
