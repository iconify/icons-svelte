<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0yso1ymp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0yso1ymp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:egg-off" {...props}></Icon>
