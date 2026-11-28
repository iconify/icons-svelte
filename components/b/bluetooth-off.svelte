<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbs3iqbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbs3iqbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bluetooth-off" {...props}></Icon>
