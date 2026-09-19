<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlej7bzzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlej7bzzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-patient-1" {...props}></Icon>
