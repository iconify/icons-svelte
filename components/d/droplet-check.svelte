<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrz19cbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrz19cbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-check" {...props}></Icon>
