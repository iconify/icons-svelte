<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6n17-uvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6n17-uvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dna-off" {...props}></Icon>
