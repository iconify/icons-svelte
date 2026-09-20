<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncy1n-byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="ncy1n-byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-right-long" {...props}></Icon>
