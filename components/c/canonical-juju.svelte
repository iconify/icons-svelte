<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfyiqcmob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfyiqcmob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:canonical-juju" {...props}></Icon>
