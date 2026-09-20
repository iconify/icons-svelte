<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_txi0raq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_txi0raq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bullet-point-expressive" {...props}></Icon>
