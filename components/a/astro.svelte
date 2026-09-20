<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpbp98unh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpbp98unh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:astro" {...props}></Icon>
