<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhqc-30ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhqc-30ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-heart-variant" {...props}></Icon>
