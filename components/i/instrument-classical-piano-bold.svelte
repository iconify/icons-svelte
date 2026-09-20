<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjodv2swo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjodv2swo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:instrument-classical-piano-bold" {...props}></Icon>
