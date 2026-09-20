<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irf8r5nfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irf8r5nfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fox" {...props}></Icon>
