<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siwlnswnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siwlnswnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:p5dotjs" {...props}></Icon>
