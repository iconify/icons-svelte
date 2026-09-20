<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyr-4ca5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyr-4ca5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nextflow" {...props}></Icon>
